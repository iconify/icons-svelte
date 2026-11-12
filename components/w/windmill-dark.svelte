<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6zpiyb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6zpiyb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windmill-dark" {...props}></Icon>
