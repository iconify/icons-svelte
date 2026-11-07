<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/r/rs66d5_uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="rs66d5_uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scaling-bold-duotone" {...props}></Icon>
