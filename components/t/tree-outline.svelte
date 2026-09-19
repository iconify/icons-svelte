<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1b8itgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="df1b8itgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-outline" {...props}></Icon>
