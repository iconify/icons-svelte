<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eldv-d4uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eldv-d4uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:spinner-earring" {...props}></Icon>
