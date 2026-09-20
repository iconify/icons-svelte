<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8u1fd4tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8u1fd4tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transfer-left" {...props}></Icon>
