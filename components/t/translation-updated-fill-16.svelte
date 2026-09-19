<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srky2gbgm.css';
import '../../css/n/nkc71p2ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srky2gbgm"/><path class="nkc71p2ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-updated-fill-16" {...props}></Icon>
