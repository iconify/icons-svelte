<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pga6wlxad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pga6wlxad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tiddlywiki" {...props}></Icon>
