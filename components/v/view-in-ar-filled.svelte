<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0cmkm9pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0cmkm9pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:view-in-ar-filled" {...props}></Icon>
