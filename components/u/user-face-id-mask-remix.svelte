<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xli1voboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xli1voboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-face-id-mask-remix" {...props}></Icon>
