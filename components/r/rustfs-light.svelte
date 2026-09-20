<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en3f2o17m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="en3f2o17m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustfs-light" {...props}></Icon>
