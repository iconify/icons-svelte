<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnvi2hutx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="dnvi2hutx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:skateboarding" {...props}></Icon>
