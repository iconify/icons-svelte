<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cevse_boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cevse_boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:square-brackets-off" {...props}></Icon>
