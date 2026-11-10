<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f30r4v8bi.css';
import '../../css/i/i8p3d6bjp.css';
import '../../css/z/z3mdksbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="f30r4v8bi"><path class="i8p3d6bjp"/><path class="z3mdksbjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:upsilon-capital" {...props}></Icon>
