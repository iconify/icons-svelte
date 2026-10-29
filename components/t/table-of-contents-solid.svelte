<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4iwckbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4iwckbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:table-of-contents-solid" {...props}></Icon>
