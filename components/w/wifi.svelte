<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zulqtnb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zulqtnb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi" {...props}></Icon>
