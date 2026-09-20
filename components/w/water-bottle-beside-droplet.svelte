<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ha6qusa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k9ha6qusa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-bottle-beside-droplet" {...props}></Icon>
