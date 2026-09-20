<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi269-bum.css';
import '../../css/r/rk3z2_bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yi269-bum"/><path class="rk3z2_bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:wrangler" {...props}></Icon>
