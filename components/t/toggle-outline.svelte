<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/al1t21i5l.css';
import '../../css/w/wi6gu6bfm.css';
import '../../css/g/g5mtd3btz.css';
import '../../css/k/kqy7zwb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="al1t21i5l"/><path class="wi6gu6bfm"/><path class="g5mtd3btz"/><path class="kqy7zwb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:toggle-outline" {...props}></Icon>
