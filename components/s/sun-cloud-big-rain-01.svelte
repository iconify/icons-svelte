<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p7qo25lsm.css';
import '../../css/r/rusiocb7e.css';
import '../../css/c/clkta5wrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p7qo25lsm"/><path class="rusiocb7e"/><path class="clkta5wrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-cloud-big-rain-01" {...props}></Icon>
