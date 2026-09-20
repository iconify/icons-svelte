<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5mt81ygv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5mt81ygv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vector-triangle" {...props}></Icon>
