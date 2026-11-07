<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt_ga9x1x.css';
import '../../css/k/k2crqybes.css';
import '../../css/l/lcil0k4ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wt_ga9x1x"/><path class="k2crqybes"/><path class="lcil0k4ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ticket-sale-outline" {...props}></Icon>
