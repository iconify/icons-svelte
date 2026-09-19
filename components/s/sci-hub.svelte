<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpru0-bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="qpru0-bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:sci-hub" {...props}></Icon>
