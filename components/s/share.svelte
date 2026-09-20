<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmr4i_btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="fmr4i_btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:share" {...props}></Icon>
