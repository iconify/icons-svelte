<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rrkjydeid.css';
import '../../css/c/clhe63_8r.css';
import '../../css/w/w2ixxib2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="rrkjydeid"/><path vector-effect="non-scaling-stroke" class="clhe63_8r"/><path vector-effect="non-scaling-stroke" class="w2ixxib2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:tabs" {...props}></Icon>
