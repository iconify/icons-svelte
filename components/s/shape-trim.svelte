<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx2ynm8se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx2ynm8se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-trim" {...props}></Icon>
