<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eov14kbcx.css';
import '../../css/e/e71xpcq7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eov14kbcx"/><path class="e71xpcq7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stop-bold-duotone" {...props}></Icon>
