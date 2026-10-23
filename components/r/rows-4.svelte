<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tff-mlbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tff-mlbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rows-4" {...props}></Icon>
