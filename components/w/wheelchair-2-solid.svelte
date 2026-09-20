<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg2s2rtgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tg2s2rtgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wheelchair-2-solid" {...props}></Icon>
