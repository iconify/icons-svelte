<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlyrpgbor.css';
import '../../css/u/u7_wj4bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlyrpgbor"/><path class="u7_wj4bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:weigher-bold-duotone" {...props}></Icon>
