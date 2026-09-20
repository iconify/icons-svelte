<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/w/wmzd77btb.css';
import '../../css/f/fa2xeyb1j.css';
import '../../css/l/lvqax5g6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="wmzd77btb"/><path class="fa2xeyb1j"/><path class="lvqax5g6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:wallet-alt" {...props}></Icon>
