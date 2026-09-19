<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf7vyfbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tf7vyfbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:vest-patches" {...props}></Icon>
