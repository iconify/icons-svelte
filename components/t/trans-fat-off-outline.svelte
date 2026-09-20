<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba9b20lou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9b20lou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trans-fat-off-outline" {...props}></Icon>
