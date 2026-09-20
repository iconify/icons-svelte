<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj7dycb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zj7dycb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rupee" {...props}></Icon>
