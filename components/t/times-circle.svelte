<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuqt_yb-q.css';
import '../../css/k/kgyn-hblg.css';
import '../../css/d/ddohpfdpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="kgyn-hblg"/><path class="ddohpfdpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:times-circle" {...props}></Icon>
