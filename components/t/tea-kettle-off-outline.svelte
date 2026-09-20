<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h98xfabbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h98xfabbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tea-kettle-off-outline" {...props}></Icon>
