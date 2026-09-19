<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qodv1-buf.css';
import '../../css/u/u4b819bdl.css';
import '../../css/b/bw3e3bcaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qodv1-buf"/><path class="u4b819bdl"/><path class="bw3e3bcaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sushi-03" {...props}></Icon>
