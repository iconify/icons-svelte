<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfcz1lb7w.css';
import '../../css/t/tigdgqbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qfcz1lb7w"/><path class="tigdgqbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:travel" {...props}></Icon>
