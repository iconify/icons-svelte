<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfe17mbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfe17mbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scratch-blocks-filled" {...props}></Icon>
