<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnep6zbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="rnep6zbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:user-square" {...props}></Icon>
