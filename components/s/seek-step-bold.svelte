<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/o/o0n3p_e0w.css';
import '../../css/m/mzu1w-bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="to-5kdesz"><path class="o0n3p_e0w"/><path class="mzu1w-bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-step-bold" {...props}></Icon>
