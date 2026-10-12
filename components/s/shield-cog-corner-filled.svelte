<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/supw_uxls.css';
import '../../css/a/a_g1h2blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="supw_uxls"/><path clip-rule="evenodd" class="a_g1h2blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-cog-corner-filled" {...props}></Icon>
