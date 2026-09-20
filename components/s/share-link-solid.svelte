<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh1gm4byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zh1gm4byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:share-link-solid" {...props}></Icon>
