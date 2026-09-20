<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueuawwqlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueuawwqlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stop-alert" {...props}></Icon>
