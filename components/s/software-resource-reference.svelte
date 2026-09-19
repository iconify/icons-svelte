<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt5up1vxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qt5up1vxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:software-resource-reference" {...props}></Icon>
