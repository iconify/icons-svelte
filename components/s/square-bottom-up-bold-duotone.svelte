<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/d/d-j_pg1wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="d-j_pg1wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-bottom-up-bold-duotone" {...props}></Icon>
