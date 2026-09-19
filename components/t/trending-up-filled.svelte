<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg1nxcods.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1nxcods"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trending-up-filled" {...props}></Icon>
