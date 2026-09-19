<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x84f6ibiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x84f6ibiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:save-sharp" {...props}></Icon>
