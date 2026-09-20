<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmval1bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmval1bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tools" {...props}></Icon>
