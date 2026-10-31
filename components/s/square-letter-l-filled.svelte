<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elsluvvlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elsluvvlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-l-filled" {...props}></Icon>
