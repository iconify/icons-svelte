<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jbeyhdbgx.css';
import '../../css/h/hbaow-b7m.css';
import '../../css/d/dkcq8bbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jbeyhdbgx"/><path class="hbaow-b7m"/><path class="dkcq8bbuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:taco-01" {...props}></Icon>
