<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc7tfnbgj.css';
import '../../css/e/eu3o_ilxw.css';
import '../../css/b/b1ql3zb2y.css';
import '../../css/g/g6vgndbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tc7tfnbgj"/><path class="eu3o_ilxw"/><path class="b1ql3zb2y"/><path class="g6vgndbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:threedsmax" {...props}></Icon>
