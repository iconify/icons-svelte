<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eru_cbbks.css';
import '../../css/g/gnuh1n3mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eru_cbbks"/><path class="gnuh1n3mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:webassembly" {...props}></Icon>
