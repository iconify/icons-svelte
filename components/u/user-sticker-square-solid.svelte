<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nyzz8mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c8nyzz8mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-sticker-square-solid" {...props}></Icon>
