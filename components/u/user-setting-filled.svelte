<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrqtygbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrqtygbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-setting-filled" {...props}></Icon>
