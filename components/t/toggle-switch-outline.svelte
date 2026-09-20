<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4_k3cbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4_k3cbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toggle-switch-outline" {...props}></Icon>
