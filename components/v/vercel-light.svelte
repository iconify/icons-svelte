<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzzr1mstp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":222};
const content = `<path class="gzzr1mstp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vercel-light" {...props}></Icon>
