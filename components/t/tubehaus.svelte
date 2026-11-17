<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxqmevb6p.css';
import '../../css/p/pan7dlbeh.css';
import '../../css/s/sjj76ybgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="uxqmevb6p"/><path class="pan7dlbeh"/><path class="sjj76ybgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubehaus" {...props}></Icon>
