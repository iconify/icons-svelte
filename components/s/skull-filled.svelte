<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_j47cp6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_j47cp6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:skull-filled" {...props}></Icon>
