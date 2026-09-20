<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scey3vbcr.css';
import '../../css/n/nutzz_b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="scey3vbcr"/><path clip-rule="evenodd" class="nutzz_b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:snapshot-16" {...props}></Icon>
