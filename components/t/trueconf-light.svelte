<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neg8u-b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="neg8u-b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trueconf-light" {...props}></Icon>
