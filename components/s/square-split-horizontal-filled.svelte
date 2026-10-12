<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6c5cdb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6c5cdb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-split-horizontal-filled" {...props}></Icon>
