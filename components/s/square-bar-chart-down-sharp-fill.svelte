<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdr0sobjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdr0sobjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-down-sharp-fill" {...props}></Icon>
