<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cyr97l9zo.css';
import '../../css/f/f9cat0b0r.css';
import '../../css/j/j0uptwbwv.css';
import '../../css/j/j-4h9gb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cyr97l9zo"/><path class="f9cat0b0r"/><path class="j0uptwbwv"/><path class="j-4h9gb2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:sn" {...props}></Icon>
