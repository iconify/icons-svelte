<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebe8fjn1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebe8fjn1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:triangle" {...props}></Icon>
