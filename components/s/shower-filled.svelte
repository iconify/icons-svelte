<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykr98khrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykr98khrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shower-filled" {...props}></Icon>
