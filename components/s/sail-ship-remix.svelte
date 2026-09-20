<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq8qgzcnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kq8qgzcnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sail-ship-remix" {...props}></Icon>
