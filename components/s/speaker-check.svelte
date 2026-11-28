<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy9m0zb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy9m0zb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:speaker-check" {...props}></Icon>
