<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6a-abur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6a-abur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shapes-filled" {...props}></Icon>
