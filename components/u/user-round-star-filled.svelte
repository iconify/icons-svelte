<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qopej0bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qopej0bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-star-filled" {...props}></Icon>
