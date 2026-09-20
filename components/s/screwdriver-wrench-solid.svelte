<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds6j52bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ds6j52bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:screwdriver-wrench-solid" {...props}></Icon>
