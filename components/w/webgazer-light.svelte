<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4tn-kbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4tn-kbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webgazer-light" {...props}></Icon>
