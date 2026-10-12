<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjvc8yb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjvc8yb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trailer-filled" {...props}></Icon>
