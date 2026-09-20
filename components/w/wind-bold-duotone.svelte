<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gc7mvhrpq.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/z/z9v-29bvh.css';
import '../../css/v/vnyou5k3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gc7mvhrpq"/><g class="mc2zb0bvp"><path class="z9v-29bvh"/><path class="vnyou5k3z"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wind-bold-duotone" {...props}></Icon>
