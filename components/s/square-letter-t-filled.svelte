<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we0b4da0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="we0b4da0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-t-filled" {...props}></Icon>
