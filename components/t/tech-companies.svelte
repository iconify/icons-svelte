<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydblyy4jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydblyy4jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:tech-companies" {...props}></Icon>
