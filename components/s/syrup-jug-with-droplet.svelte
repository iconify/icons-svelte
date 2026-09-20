<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdj2-4vry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cdj2-4vry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug-with-droplet" {...props}></Icon>
