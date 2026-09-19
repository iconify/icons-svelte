<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ybl3b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h4ybl3b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:shield" {...props}></Icon>
