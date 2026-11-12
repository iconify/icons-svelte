<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyqg1bbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyqg1bbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:system76-dark" {...props}></Icon>
