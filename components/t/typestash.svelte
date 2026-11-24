<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki9s1utoq.css';
import '../../css/d/da16a4bkk.css';
import '../../css/i/ieb391brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ki9s1utoq"/><path class="da16a4bkk"/><path class="ieb391brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typestash" {...props}></Icon>
