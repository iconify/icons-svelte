<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc75y-sag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc75y-sag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-donut-variant" {...props}></Icon>
