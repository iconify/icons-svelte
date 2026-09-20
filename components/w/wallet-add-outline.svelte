<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwe524shh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe524shh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wallet-add-outline" {...props}></Icon>
