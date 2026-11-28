<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/o/o-vq384-b.css';
import '../../css/f/f7x0orx7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mie31z6an"/><circle class="o-vq384-b"/><path class="f7x0orx7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-square" {...props}></Icon>
