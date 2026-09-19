<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd56lrbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd56lrbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:workflow-alt" {...props}></Icon>
