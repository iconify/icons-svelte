<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejbswtb9o.css';
import '../../css/d/dkt4s1bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejbswtb9o"/><path class="dkt4s1bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:vehicle-filled" {...props}></Icon>
