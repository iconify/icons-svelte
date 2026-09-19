<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dazc_hbbb.css';
import '../../css/i/iybw-7did.css';
import '../../css/z/z63rirbsm.css';
import '../../css/f/fn4mlcb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dazc_hbbb"/><path class="iybw-7did"/><path class="z63rirbsm"/><path class="fn4mlcb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sun-outline" {...props}></Icon>
