<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_1mxbb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_1mxbb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:watch-1-remix" {...props}></Icon>
