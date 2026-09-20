<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywsxvimlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywsxvimlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-interface-filled" {...props}></Icon>
