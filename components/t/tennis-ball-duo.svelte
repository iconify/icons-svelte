<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ch09qbfwl.css';
import '../../css/b/bcoq-rbfh.css';
import '../../css/h/habi4zc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ch09qbfwl"/><path class="bcoq-rbfh"/><path class="habi4zc9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tennis-ball-duo" {...props}></Icon>
