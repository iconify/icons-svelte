<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhugqhbem.css';
import '../../css/c/ct2edwbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhugqhbem"/><path class="ct2edwbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-off-filled" {...props}></Icon>
