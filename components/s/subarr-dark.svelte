<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu_s1bbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wu_s1bbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subarr-dark" {...props}></Icon>
