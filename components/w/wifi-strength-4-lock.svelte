<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9hj6xbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9hj6xbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-4-lock" {...props}></Icon>
