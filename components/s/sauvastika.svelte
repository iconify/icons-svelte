<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zob4dxq5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zob4dxq5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sauvastika" {...props}></Icon>
