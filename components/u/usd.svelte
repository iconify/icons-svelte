<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m51pp1z2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1792};
const content = `<path class="m51pp1z2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:usd" {...props}></Icon>
