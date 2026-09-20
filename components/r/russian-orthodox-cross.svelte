<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edrcmr_wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="edrcmr_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:russian-orthodox-cross" {...props}></Icon>
