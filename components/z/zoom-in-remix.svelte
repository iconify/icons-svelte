<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diq48hb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="diq48hb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:zoom-in-remix" {...props}></Icon>
