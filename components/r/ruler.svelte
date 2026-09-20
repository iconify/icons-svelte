<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9sohlbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="u9sohlbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ruler" {...props}></Icon>
