<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hho220g3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hho220g3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scooter-fill" {...props}></Icon>
