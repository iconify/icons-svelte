<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhslucb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zhslucb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face" {...props}></Icon>
