<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kiglhf1ae.css';
import '../../css/n/nzmqz3bvt.css';
import '../../css/l/l1jur_bpp.css';
import '../../css/o/onqn7xbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kiglhf1ae"/><path class="nzmqz3bvt"/><path class="l1jur_bpp"/><path class="onqn7xbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-linear" {...props}></Icon>
