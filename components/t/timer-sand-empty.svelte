<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckge42buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckge42buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-sand-empty" {...props}></Icon>
