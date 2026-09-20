<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkrcpbcwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkrcpbcwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector" {...props}></Icon>
