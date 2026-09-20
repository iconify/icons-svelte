<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpyrxwlxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpyrxwlxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trade-republic" {...props}></Icon>
