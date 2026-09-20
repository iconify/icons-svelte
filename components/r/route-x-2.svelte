<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc49-kpvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc49-kpvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:route-x-2" {...props}></Icon>
