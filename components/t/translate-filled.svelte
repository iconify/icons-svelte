<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guak-rt4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guak-rt4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:translate-filled" {...props}></Icon>
