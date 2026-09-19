<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmg2hgb8g.css';
import '../../css/d/dcxprjszn.css';
import '../../css/s/sjrvryb6o.css';
import '../../css/h/hgv60rb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pmg2hgb8g"/><circle class="dcxprjszn"/><circle class="sjrvryb6o"/><path class="hgv60rb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:share-social-outline" {...props}></Icon>
