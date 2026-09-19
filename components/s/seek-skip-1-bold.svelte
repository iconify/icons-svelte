<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/g/g3xgywz_t.css';
import '../../css/k/k433me6_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="to-5kdesz"><path class="g3xgywz_t"/><path class="k433me6_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-skip-1-bold" {...props}></Icon>
