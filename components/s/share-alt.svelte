<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4h_4poq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uj4h_4poq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:share-alt" {...props}></Icon>
