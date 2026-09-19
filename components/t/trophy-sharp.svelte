<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyam1zhwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cyam1zhwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trophy-sharp" {...props}></Icon>
