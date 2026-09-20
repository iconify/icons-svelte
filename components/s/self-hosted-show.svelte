<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pixd3le1c.css';
import '../../css/n/nspe8_bkd.css';
import '../../css/r/r-0tybctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="pixd3le1c"/><path class="nspe8_bkd"/><path class="r-0tybctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-show" {...props}></Icon>
