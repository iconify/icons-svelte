<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m9v85de3k.css';
import '../../css/n/nhknek4be.css';
import '../../css/a/a2e2ku32f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m9v85de3k"/><path class="nhknek4be"/><path class="a2e2ku32f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-compact" {...props}></Icon>
