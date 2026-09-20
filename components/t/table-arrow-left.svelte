<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1lmppv5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1lmppv5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-arrow-left" {...props}></Icon>
