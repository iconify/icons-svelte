<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xssurv7iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xssurv7iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:web-awesome" {...props}></Icon>
