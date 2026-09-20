<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-wf3bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-wf3bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-flatbed-car" {...props}></Icon>
