<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w47h2ubnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w47h2ubnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typesense" {...props}></Icon>
