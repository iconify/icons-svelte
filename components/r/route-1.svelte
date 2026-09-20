<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsy148som.css';
import '../../css/f/fg4g6tbff.css';
import '../../css/d/d7c0xbofg.css';
import '../../css/z/zjo456biz.css';
import '../../css/o/ou9-8bc_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="hsy148som"/><path clip-rule="evenodd" class="fg4g6tbff"/><path class="d7c0xbofg"/><path clip-rule="evenodd" class="zjo456biz"/><path class="ou9-8bc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:route-1" {...props}></Icon>
