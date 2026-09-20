<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uprp52apm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uprp52apm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wakapi-dark" {...props}></Icon>
