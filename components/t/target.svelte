<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wodzcw80r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wodzcw80r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:target" {...props}></Icon>
