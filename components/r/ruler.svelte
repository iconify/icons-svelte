<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4eeg6vrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4eeg6vrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ruler" {...props}></Icon>
