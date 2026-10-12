<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew50tebjg.css';
import '../../css/n/n4qsi-ucz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew50tebjg"/><path class="n4qsi-ucz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-x-filled" {...props}></Icon>
