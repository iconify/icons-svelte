<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv815x65j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv815x65j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-amount-down-alt" {...props}></Icon>
