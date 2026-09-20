<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am47zfead.css';
import '../../css/k/kzui9exaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="am47zfead"/><path class="kzui9exaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:zoom-in" {...props}></Icon>
