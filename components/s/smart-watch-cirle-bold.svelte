<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_w3injsq.css';
import '../../css/r/rwg8vfj3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_w3injsq"/><path class="rwg8vfj3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-watch-cirle-bold" {...props}></Icon>
