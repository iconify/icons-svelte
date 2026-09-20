<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf0o-hxpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf0o-hxpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-2-lock-open" {...props}></Icon>
