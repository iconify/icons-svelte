<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgc2aw0_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgc2aw0_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:undo-alt" {...props}></Icon>
