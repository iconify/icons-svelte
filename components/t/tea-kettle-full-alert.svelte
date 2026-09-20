<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk-19x-6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-19x-6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tea-kettle-full-alert" {...props}></Icon>
