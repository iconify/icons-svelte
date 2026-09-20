<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntc5j9rdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntc5j9rdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tune-vertical" {...props}></Icon>
