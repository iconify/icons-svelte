<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgnbte-qu.css';
import '../../css/c/cxtw4ab8u.css';
import '../../css/c/c2pyp_bvu.css';
import '../../css/h/hmxq_r-te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zgnbte-qu"/><path class="cxtw4ab8u"/><path class="c2pyp_bvu"/><path class="hmxq_r-te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowflake-20" {...props}></Icon>
