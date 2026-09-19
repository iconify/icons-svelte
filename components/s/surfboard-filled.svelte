<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdvz9kbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvz9kbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:surfboard-filled" {...props}></Icon>
