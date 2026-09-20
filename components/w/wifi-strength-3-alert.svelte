<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxr0uizak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxr0uizak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-3-alert" {...props}></Icon>
