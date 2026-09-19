<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fvstvtsqi.css';
import '../../css/e/ehmjtr_qq.css';
import '../../css/o/oh-gh1bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fvstvtsqi"/><path clip-rule="evenodd" class="ehmjtr_qq"/><path class="oh-gh1bfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:virus-outline" {...props}></Icon>
