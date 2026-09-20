<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5et7lbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5et7lbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tab-plus" {...props}></Icon>
