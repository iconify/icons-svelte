<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irl9z8uwq.css';
import '../../css/i/ioz8g2bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irl9z8uwq"/><path class="ioz8g2bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-html5-outline" {...props}></Icon>
