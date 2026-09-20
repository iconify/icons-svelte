<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvzjp4biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvzjp4biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-aeroplane-outline" {...props}></Icon>
