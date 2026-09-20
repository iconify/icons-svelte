<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmiv2pbgq.css';
import '../../css/v/vh-56ab7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmiv2pbgq"/><path class="vh-56ab7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:vmware" {...props}></Icon>
