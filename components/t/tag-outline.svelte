<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/u6omv9ofk.css';
import '../../css/e/e4p8vf7to.css';
import '../../css/g/glovd0xbt.css';
import '../../css/w/w45-n2gzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="u6omv9ofk"/><path class="e4p8vf7to"/><path class="glovd0xbt"/><path class="w45-n2gzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tag-outline" {...props}></Icon>
