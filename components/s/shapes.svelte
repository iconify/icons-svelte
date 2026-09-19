<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqz39y55m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz39y55m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shapes" {...props}></Icon>
