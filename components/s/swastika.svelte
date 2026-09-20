<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2uaob4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rp2uaob4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:swastika" {...props}></Icon>
