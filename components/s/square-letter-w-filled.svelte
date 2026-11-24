<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl3j90-dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dl3j90-dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-w-filled" {...props}></Icon>
