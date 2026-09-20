<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqp006-vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqp006-vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-0-warning" {...props}></Icon>
