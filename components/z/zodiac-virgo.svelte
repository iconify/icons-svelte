<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn_4rw0pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn_4rw0pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:zodiac-virgo" {...props}></Icon>
