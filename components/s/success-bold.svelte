<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysamgs33o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysamgs33o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:success-bold" {...props}></Icon>
