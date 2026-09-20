<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f06ytdb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="f06ytdb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:solar-eclipse" {...props}></Icon>
