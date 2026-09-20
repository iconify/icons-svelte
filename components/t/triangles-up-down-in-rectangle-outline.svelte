<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0knp0bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f0knp0bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangles-up-down-in-rectangle-outline" {...props}></Icon>
