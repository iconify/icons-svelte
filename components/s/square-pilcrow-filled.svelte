<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veaxrgwgs.css';
import '../../css/o/op-da8bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veaxrgwgs"/><path clip-rule="evenodd" class="op-da8bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-pilcrow-filled" {...props}></Icon>
