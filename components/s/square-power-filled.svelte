<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1pf1jbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1pf1jbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-power-filled" {...props}></Icon>
