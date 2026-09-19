<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czhwh68px.css';
import '../../css/n/n4x3x3ysu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="czhwh68px"/><path class="n4x3x3ysu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:watch-sharp" {...props}></Icon>
