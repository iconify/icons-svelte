<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw1wyjsjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zw1wyjsjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:store-1-remix" {...props}></Icon>
