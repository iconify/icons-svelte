<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2j2plflq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d2j2plflq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-alt-2-outline" {...props}></Icon>
