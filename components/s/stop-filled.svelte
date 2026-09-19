<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhnnvfbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhnnvfbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:stop-filled" {...props}></Icon>
