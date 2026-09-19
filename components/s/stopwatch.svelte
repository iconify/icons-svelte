<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzgys3b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzgys3b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:stopwatch" {...props}></Icon>
