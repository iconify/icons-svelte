<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/x/xb_8t6b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="xb_8t6b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-square-bold-duotone" {...props}></Icon>
