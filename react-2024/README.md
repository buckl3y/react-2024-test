## Notes

build scripts are located in `packages.json` under `scripts:`
install React dev tools in browser
install ES7 React/Redux/React-Native Extension in VSCode
added this to vite.config.js

server: {
port:3000,
}

install taiwind `npm install tailwindcss @tailwindcss/vite`

iterate over an array

<ul>
      { names.map((name, index) => (
        <li key={index}>{name}</li>
      ))}
</ul>

Tailwind CSS style
`<div className='text-5xl'>App</div>`

Inline CSS style with CSS Object
const styles = {
color: 'red',
fontSize: '55px',
}
