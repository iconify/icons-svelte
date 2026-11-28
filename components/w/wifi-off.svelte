<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzycj6brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzycj6brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wifi-off" {...props}></Icon>
