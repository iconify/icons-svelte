<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haqop-b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="haqop-b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zodiaccapricorn" {...props}></Icon>
