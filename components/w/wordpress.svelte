<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhuwsobbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":995.329,"height":1000};
const content = `<path class="bhuwsobbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:wordpress" {...props}></Icon>
