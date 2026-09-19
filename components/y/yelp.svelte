<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc9g4or4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":488};
const content = `<path class="lc9g4or4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:yelp" {...props}></Icon>
