<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqq221b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqq221b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector-outline" {...props}></Icon>
