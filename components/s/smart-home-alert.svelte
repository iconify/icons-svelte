<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd8kj4bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8kj4bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smart-home-alert" {...props}></Icon>
