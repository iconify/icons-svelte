<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-e8ugb3c.css';
import '../../css/d/d-svt8bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-e8ugb3c"/><path class="d-svt8bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:speech-bubble-alert-rtl" {...props}></Icon>
