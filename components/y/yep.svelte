<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsdaedbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dsdaedbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:yep" {...props}></Icon>
