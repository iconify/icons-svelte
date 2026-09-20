<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ajh-k9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p6ajh-k9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:synchronize-disable-solid" {...props}></Icon>
