<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhs_bvkid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhs_bvkid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-terminal-filled" {...props}></Icon>
