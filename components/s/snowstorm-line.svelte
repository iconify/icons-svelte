<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt3x90b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3x90b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-line" {...props}></Icon>
