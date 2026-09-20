<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qrheekb0d.css';
import '../../css/s/srajr7bws.css';
import '../../css/r/rfjwc7d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qrheekb0d"/><path class="srajr7bws"/><path class="rfjwc7d-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:table-heart" {...props}></Icon>
