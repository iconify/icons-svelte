<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks7isf27w.css';
import '../../css/t/tdaucbcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks7isf27w"/><path class="tdaucbcdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:server-off-filled" {...props}></Icon>
