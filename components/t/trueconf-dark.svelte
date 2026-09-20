<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4jb__b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4jb__b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trueconf-dark" {...props}></Icon>
