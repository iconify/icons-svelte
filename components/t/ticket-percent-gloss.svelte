<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3l1uf5yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3l1uf5yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-percent-gloss" {...props}></Icon>
