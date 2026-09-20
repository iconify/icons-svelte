<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5q1bccnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5q1bccnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vkontakte-circle" {...props}></Icon>
