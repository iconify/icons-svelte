<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7xrf5b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7xrf5b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teddycloud-dark" {...props}></Icon>
