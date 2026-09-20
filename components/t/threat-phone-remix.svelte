<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df-d0zb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="df-d0zb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:threat-phone-remix" {...props}></Icon>
