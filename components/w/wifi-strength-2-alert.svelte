<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oosyq6bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oosyq6bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-2-alert" {...props}></Icon>
