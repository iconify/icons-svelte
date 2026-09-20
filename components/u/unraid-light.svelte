<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypl4acb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypl4acb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unraid-light" {...props}></Icon>
