<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2getkc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2getkc1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:users-collaboration-filled" {...props}></Icon>
