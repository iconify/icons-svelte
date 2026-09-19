<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0whszb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0whszb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:truck-filled" {...props}></Icon>
