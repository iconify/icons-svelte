<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvv3hf9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzvv3hf9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-2-horizontal-start-fill" {...props}></Icon>
