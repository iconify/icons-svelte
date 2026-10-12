<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfa1y2pwb.css';
import '../../css/l/l_fae7rzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfa1y2pwb"/><path class="l_fae7rzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shredder-filled" {...props}></Icon>
