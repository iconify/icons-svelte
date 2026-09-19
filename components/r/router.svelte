<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx2cbsiiy.css';
import '../../css/u/us9oalb-g.css';
import '../../css/n/n2o677b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx2cbsiiy"/><path class="us9oalb-g"/><path class="n2o677b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:router" {...props}></Icon>
