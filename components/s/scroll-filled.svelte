<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luch8eh8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="luch8eh8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scroll-filled" {...props}></Icon>
