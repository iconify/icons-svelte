<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr30gg_qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vr30gg_qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subscription-cashflow-solid" {...props}></Icon>
