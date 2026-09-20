<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0xzisoev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0xzisoev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:searxng" {...props}></Icon>
