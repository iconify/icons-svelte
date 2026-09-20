<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kobx8zbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kobx8zbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-duotone" {...props}></Icon>
