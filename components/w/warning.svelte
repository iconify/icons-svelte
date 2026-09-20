<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/o/o-wjxl3tj.css';
import '../../css/f/flen3tbdj.css';
import '../../css/r/risxovbta.css';
import '../../css/z/z-9e2yrmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVG9i8vndUf" class="n1mjunbsu"><path class="o-wjxl3tj"/></mask><g class="flen3tbdj"><path class="risxovbta"/><path mask="url(#SVG9i8vndUf)" class="z-9e2yrmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:warning" {...props}></Icon>
