<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7pj_5bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":741};
const content = `<path class="x7pj_5bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:speed" {...props}></Icon>
