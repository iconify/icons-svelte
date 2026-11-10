<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou38wj13w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou38wj13w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-exclamation-point-filled" {...props}></Icon>
