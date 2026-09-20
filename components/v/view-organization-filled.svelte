<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/der5ev0pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="der5ev0pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:view-organization-filled" {...props}></Icon>
