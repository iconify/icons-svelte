<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/k/k4qeo4hhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="k4qeo4hhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slash-square-bold-duotone" {...props}></Icon>
