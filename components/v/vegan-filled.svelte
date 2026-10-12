<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8idyf61c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n8idyf61c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vegan-filled" {...props}></Icon>
