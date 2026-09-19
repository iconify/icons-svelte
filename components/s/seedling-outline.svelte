<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osw0yxbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="osw0yxbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seedling-outline" {...props}></Icon>
