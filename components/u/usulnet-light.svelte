<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfqh065wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfqh065wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usulnet-light" {...props}></Icon>
