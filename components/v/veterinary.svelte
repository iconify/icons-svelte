<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqlzqm85m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zqlzqm85m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:veterinary" {...props}></Icon>
