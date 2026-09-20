<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1kz4tlbg.css';
import '../../css/d/d-svt8bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g1kz4tlbg"/><path class="d-svt8bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:speech-bubble-add-rtl" {...props}></Icon>
