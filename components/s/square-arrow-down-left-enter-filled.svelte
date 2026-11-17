<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyk9e30qv.css';
import '../../css/t/ta5emobsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyk9e30qv"/><path class="ta5emobsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-down-left-enter-filled" {...props}></Icon>
