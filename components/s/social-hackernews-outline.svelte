<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bycj2bqiy.css';
import '../../css/n/nfo4jpdxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bycj2bqiy"/><path class="nfo4jpdxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-hackernews-outline" {...props}></Icon>
