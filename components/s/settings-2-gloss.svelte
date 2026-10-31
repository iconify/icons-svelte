<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lryf-jbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lryf-jbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:settings-2-gloss" {...props}></Icon>
