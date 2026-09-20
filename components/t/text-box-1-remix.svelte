<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl-a6dbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yl-a6dbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-box-1-remix" {...props}></Icon>
