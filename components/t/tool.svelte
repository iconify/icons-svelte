<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wncb6lb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wncb6lb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tool" {...props}></Icon>
