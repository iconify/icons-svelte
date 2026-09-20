<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzsu600ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzsu600ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:star-2" {...props}></Icon>
