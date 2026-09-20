<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl8o5gbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8o5gbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trackpad" {...props}></Icon>
