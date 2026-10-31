<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr8gclxzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr8gclxzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-y-filled" {...props}></Icon>
