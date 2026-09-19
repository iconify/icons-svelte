<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r79y_fa2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r79y_fa2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-off-fill" {...props}></Icon>
