<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7-r17bww.css';
import '../../css/e/eyfhqgb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w7-r17bww"/><path class="eyfhqgb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidyquest-dark" {...props}></Icon>
