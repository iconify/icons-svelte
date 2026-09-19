<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_c39byp.css';
import '../../css/a/aqyw_snoc.css';
import '../../css/i/idkd0abbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_c39byp"/><path class="aqyw_snoc"/><path class="idkd0abbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:trip-advisor" {...props}></Icon>
