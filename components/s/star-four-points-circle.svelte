<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfcdez32f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcdez32f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points-circle" {...props}></Icon>
