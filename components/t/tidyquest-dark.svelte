<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw3h4vb5b.css';
import '../../css/e/eyfhqgb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cw3h4vb5b"/><path class="eyfhqgb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidyquest-dark" {...props}></Icon>
