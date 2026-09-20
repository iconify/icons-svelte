<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da2ax3dpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":47,"height":64};
const content = `<path class="da2ax3dpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tezos" {...props}></Icon>
