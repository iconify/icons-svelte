<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2r7znbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2r7znbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sandwich-filled" {...props}></Icon>
