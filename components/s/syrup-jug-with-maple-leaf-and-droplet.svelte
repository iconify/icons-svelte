<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz5xp2bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nz5xp2bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug-with-maple-leaf-and-droplet" {...props}></Icon>
