<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7rb8xakk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7rb8xakk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi-info" {...props}></Icon>
