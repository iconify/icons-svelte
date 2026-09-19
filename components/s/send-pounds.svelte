<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hogky4pfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hogky4pfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-pounds" {...props}></Icon>
