<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e488r-b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e488r-b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:spoon-filled" {...props}></Icon>
