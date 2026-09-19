<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip29fjbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip29fjbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-critical" {...props}></Icon>
