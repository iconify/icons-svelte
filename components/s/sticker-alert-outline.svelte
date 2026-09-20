<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yptj8wb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yptj8wb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticker-alert-outline" {...props}></Icon>
