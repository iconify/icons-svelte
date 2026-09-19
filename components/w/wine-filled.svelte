<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6_z9abcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6_z9abcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wine-filled" {...props}></Icon>
