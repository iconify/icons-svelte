<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zddxcdb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zddxcdb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-skip-1-outline" {...props}></Icon>
