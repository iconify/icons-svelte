<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyll-cbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyll-cbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yelp-light" {...props}></Icon>
