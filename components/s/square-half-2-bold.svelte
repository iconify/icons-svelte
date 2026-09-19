<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zaznb6ikb.css';
import '../../css/a/a3dvf63xo.css';
import '../../css/j/j60knyzzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="zaznb6ikb"/><path class="a3dvf63xo"/><path class="j60knyzzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half-2-bold" {...props}></Icon>
