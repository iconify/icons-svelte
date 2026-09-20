<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljb72pblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljb72pblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-protection-1" {...props}></Icon>
