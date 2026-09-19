<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj9cadb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oj9cadb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:share" {...props}></Icon>
