<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr86svbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hr86svbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wrench-outline" {...props}></Icon>
