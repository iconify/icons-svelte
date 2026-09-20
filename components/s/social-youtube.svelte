<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt3y6rb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zt3y6rb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-youtube" {...props}></Icon>
