<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei9w6ufyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ei9w6ufyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:texture" {...props}></Icon>
