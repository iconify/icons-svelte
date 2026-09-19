<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dx3q3ccpo.css';
import '../../css/v/v4h1cqbwn.css';
import '../../css/a/a-1j1xy1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dx3q3ccpo"/><path class="v4h1cqbwn"/><path clip-rule="evenodd" class="a-1j1xy1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tractor" {...props}></Icon>
