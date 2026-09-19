<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-7-j98_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-7-j98_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-alt-filled" {...props}></Icon>
