<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/fj8mgub1r.css';
import '../../css/y/y-i__ff-j.css';
import '../../css/z/z7h9dmbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="fj8mgub1r"/><path class="y-i__ff-j"/><rect class="z7h9dmbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:three-d-box-square" {...props}></Icon>
