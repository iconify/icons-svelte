<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdis0vbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdis0vbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-2-line" {...props}></Icon>
