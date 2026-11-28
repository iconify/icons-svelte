<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi8j84bbv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dmacaebrz.css';
import '../../css/k/koq907bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi8j84bbv secondary"/><g class="dt0cm9dhy primary"><path class="dmacaebrz"/><path class="koq907bzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:slice-duo" {...props}></Icon>
