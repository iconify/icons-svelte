<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fxn98z4kn.css';
import '../../css/c/cbgocdc0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fxn98z4kn"/><rect transform="matrix(-1 0 0 1 7 13.36)" class="cbgocdc0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:signal-status-low" {...props}></Icon>
