<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-r3gkb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r3gkb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:volume-1-filled" {...props}></Icon>
