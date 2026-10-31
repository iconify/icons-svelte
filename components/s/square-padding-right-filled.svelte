<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izzk8ehcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izzk8ehcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-padding-right-filled" {...props}></Icon>
