<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixj8ylb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ixj8ylb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:speaker-2-remix" {...props}></Icon>
