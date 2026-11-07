<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k66ipdb2y.css';
import '../../css/u/u806m8xap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k66ipdb2y"/><path class="u806m8xap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stopwatch-pause-bold" {...props}></Icon>
