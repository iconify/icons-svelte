<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo6udlbzj.css';
import '../../css/t/tdry5hmhi.css';
import '../../css/j/j8a3oubxj.css';
import '../../css/v/vxeo1uj4t.css';
import '../../css/b/b-mfwxbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo6udlbzj"/><path class="tdry5hmhi"/><ellipse class="j8a3oubxj"/><path class="vxeo1uj4t"/><path class="b-mfwxbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:saxophone" {...props}></Icon>
