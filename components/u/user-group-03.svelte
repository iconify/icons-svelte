<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2q6ifblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2q6ifblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-group-03" {...props}></Icon>
