<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1vz8bvvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1vz8bvvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:switch-vertical" {...props}></Icon>
