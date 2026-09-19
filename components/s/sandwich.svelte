<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sqqgvebkn.css';
import '../../css/v/v1fp2tbrr.css';
import '../../css/f/fck4l8bgi.css';
import '../../css/e/exee4vbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sqqgvebkn"/><path class="v1fp2tbrr"/><path class="fck4l8bgi"/><path class="exee4vbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sandwich" {...props}></Icon>
