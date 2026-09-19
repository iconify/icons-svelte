<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jswg7kbdr.css';
import '../../css/f/fecjq6g5y.css';
import '../../css/x/xex-xd4wj.css';
import '../../css/i/idjw04bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="jswg7kbdr"/><path class="fecjq6g5y"/><path class="xex-xd4wj"/><path class="idjw04bqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wallet" {...props}></Icon>
