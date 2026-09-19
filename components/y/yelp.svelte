<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdjyr7bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="cdjyr7bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:yelp" {...props}></Icon>
