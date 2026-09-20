<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh6fpfbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh6fpfbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tux" {...props}></Icon>
