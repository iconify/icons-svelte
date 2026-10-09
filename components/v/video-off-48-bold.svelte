<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eihpo_wmr.css';
import '../../css/z/z32ck6l6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eihpo_wmr"/><path class="z32ck6l6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-off-48-bold" {...props}></Icon>
