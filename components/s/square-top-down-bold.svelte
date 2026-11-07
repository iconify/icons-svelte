<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1imhmbtv.css';
import '../../css/l/l7647cc_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e1imhmbtv"/><path class="l7647cc_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-top-down-bold" {...props}></Icon>
