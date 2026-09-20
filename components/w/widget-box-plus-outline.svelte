<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j980tzfhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j980tzfhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-box-plus-outline" {...props}></Icon>
