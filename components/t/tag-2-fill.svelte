<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axl4_ccxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axl4_ccxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tag-2-fill" {...props}></Icon>
