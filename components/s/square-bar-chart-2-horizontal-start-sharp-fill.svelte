<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imtohwlhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imtohwlhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-2-horizontal-start-sharp-fill" {...props}></Icon>
