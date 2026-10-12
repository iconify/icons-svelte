<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d01p_11kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d01p_11kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-group-filled" {...props}></Icon>
