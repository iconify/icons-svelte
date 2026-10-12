<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq9-44b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq9-44b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-up-left-filled" {...props}></Icon>
