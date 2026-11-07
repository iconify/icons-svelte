<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajy_v4bwf.css';
import '../../css/h/h9vo8yb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajy_v4bwf"/><path clip-rule="evenodd" class="h9vo8yb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speaker-minimalistic-bold" {...props}></Icon>
