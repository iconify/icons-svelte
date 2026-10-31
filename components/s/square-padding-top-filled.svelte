<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy0qvsn7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iy0qvsn7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-padding-top-filled" {...props}></Icon>
