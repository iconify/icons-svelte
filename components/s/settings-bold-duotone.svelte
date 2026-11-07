<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gce_q8bwk.css';
import '../../css/p/pahtwyu4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gce_q8bwk"/><path class="pahtwyu4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:settings-bold-duotone" {...props}></Icon>
