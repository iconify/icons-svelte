<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nubv10k4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nubv10k4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:window-alert" {...props}></Icon>
