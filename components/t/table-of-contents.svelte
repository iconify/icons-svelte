<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eoq-ilkyb.css';
import '../../css/a/ahy7r9h0a.css';
import '../../css/b/bnnnmnbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="eoq-ilkyb"/><path class="ahy7r9h0a"/><path vector-effect="non-scaling-stroke" class="bnnnmnbmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:table-of-contents" {...props}></Icon>
