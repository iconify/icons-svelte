<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix5i5ubsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ix5i5ubsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:socketdotio-dark" {...props}></Icon>
