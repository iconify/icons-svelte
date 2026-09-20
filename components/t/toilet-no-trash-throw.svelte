<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syr7h0fyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syr7h0fyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:toilet-no-trash-throw" {...props}></Icon>
