<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecn1w4bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecn1w4bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wallabag-dark" {...props}></Icon>
