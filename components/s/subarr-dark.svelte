<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or85ekbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or85ekbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subarr-dark" {...props}></Icon>
