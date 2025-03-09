generate_readme(code):
    prompt = f"```swift\n{code}\n```"
    response = client.completions.create(
        model='text-davinci-003',
        prompt=prompt,
        temperature=0.7,
        max_tokens=1000,
        n=1,
        stop=None
    )
    return response.choices[0].text.strip(https://github.com/zayan-zaya
https://files.catbox.moe/ax92lq.jpg