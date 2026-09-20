<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npq4jthxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npq4jthxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-minus-outline" {...props}></Icon>
