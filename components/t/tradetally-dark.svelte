<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scob2eb_t.css';
import '../../css/d/dl8utqb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scob2eb_t"/><path class="dl8utqb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tradetally-dark" {...props}></Icon>
