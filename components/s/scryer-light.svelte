<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-n048zgz.css';
import '../../css/h/hp98eyrqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-n048zgz"/><path class="hp98eyrqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scryer-light" {...props}></Icon>
