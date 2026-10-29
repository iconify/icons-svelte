<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qco7k5bdx.css';
import '../../css/v/vzotpc4wt.css';
import '../../css/o/o9g704bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qco7k5bdx"/><path class="vzotpc4wt wm-k"/><path class="o9g704bia wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:traffic-light-sketch" {...props}></Icon>
