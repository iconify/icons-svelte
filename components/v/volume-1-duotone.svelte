<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h4z46wbrw.css';
import '../../css/h/hbhcawbze.css';
import '../../css/s/s9rzi2bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h4z46wbrw"/><path class="hbhcawbze"/><path class="s9rzi2bzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:volume-1-duotone" {...props}></Icon>
