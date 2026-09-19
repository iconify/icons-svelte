<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz8ba9tgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b vz8ba9tgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:waveform" {...props}></Icon>
