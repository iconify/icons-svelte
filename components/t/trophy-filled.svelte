<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go13jz64q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go13jz64q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trophy-filled" {...props}></Icon>
