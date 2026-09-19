<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo09mkblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo09mkblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:row-resize-filled" {...props}></Icon>
