<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz6-4v4mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz6-4v4mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shaarli-light" {...props}></Icon>
