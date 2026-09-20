<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v54in6psp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v54in6psp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:safebox-dark" {...props}></Icon>
