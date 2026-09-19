<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4h-6kbxp.css';
import '../../css/o/ooxjw-29z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4h-6kbxp"/><path class="ooxjw-29z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:select-multiple" {...props}></Icon>
