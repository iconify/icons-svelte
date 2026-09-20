<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha9j5psdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha9j5psdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rte" {...props}></Icon>
