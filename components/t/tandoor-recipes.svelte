<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7_e5xbbg.css';
import '../../css/l/lke8sfb2b.css';
import '../../css/h/hya45hbax.css';
import '../../css/q/qqi_ahbwa.css';
import '../../css/c/cnou19b4m.css';
import '../../css/y/y1cvh44tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w7_e5xbbg"/><path class="lke8sfb2b"/><path class="hya45hbax"/><path class="qqi_ahbwa"/><path class="cnou19b4m"/><path class="y1cvh44tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tandoor-recipes" {...props}></Icon>
