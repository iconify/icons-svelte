<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i01e4cb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i01e4cb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scatter-plot" {...props}></Icon>
