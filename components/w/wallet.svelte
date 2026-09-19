<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ex_avpbej.css';
import '../../css/t/trdt80b2a.css';
import '../../css/d/d8m1e2myi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ex_avpbej"/><path class="trdt80b2a"/><path class="d8m1e2myi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wallet" {...props}></Icon>
