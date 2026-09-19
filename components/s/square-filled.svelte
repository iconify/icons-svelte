<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/butvbl16t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="butvbl16t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:square-filled" {...props}></Icon>
