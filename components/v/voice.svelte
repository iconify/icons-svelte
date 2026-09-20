<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtl_pwb1c.css';
import '../../css/b/bp9bjib7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtl_pwb1c"/><path class="bp9bjib7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:voice" {...props}></Icon>
