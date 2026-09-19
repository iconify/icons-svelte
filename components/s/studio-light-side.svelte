<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gd19j4ann.css';
import '../../css/s/sj2q25bal.css';
import '../../css/h/hxl93l8oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gd19j4ann"/><path class="sj2q25bal"/><path class="hxl93l8oj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:studio-light-side" {...props}></Icon>
