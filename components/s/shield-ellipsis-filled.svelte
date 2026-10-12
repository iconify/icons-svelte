<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpw9o4b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpw9o4b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-ellipsis-filled" {...props}></Icon>
