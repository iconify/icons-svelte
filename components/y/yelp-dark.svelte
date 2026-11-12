<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-efk4bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-efk4bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yelp-dark" {...props}></Icon>
