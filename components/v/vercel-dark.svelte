<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv5f08b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":222};
const content = `<path class="lv5f08b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vercel-dark" {...props}></Icon>
