<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n9h46nbry.css';
import '../../css/v/vjwvg5ojq.css';
import '../../css/q/qiqtkwofx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n9h46nbry"/><path class="vjwvg5ojq"/><path class="qiqtkwofx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:train" {...props}></Icon>
