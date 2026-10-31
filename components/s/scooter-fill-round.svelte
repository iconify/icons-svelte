<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp7w3xhkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7w3xhkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scooter-fill-round" {...props}></Icon>
