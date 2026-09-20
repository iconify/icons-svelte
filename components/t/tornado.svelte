<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4yx25bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l4yx25bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tornado" {...props}></Icon>
