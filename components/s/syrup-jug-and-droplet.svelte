<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4e88rqbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p4e88rqbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug-and-droplet" {...props}></Icon>
