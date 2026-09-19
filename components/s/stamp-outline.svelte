<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru0kn4bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ru0kn4bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stamp-outline" {...props}></Icon>
