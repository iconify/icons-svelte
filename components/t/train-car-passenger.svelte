<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r55r7ibth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r55r7ibth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-passenger" {...props}></Icon>
