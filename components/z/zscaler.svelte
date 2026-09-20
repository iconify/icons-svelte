<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohw9xt7rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohw9xt7rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zscaler" {...props}></Icon>
