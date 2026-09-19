<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjrmon3sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjrmon3sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-check" {...props}></Icon>
