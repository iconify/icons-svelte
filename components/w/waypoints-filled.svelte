<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo3s6ybnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo3s6ybnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:waypoints-filled" {...props}></Icon>
