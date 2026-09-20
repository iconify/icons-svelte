<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhn960soy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bhn960soy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-range" {...props}></Icon>
