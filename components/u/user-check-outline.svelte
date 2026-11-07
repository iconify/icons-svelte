<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vob1vf30q.css';
import '../../css/c/cttr9cbpd.css';
import '../../css/h/hz2a1g29i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vob1vf30q"/><path class="cttr9cbpd"/><path clip-rule="evenodd" class="hz2a1g29i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-check-outline" {...props}></Icon>
