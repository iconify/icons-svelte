<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cakg9fd0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cakg9fd0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:symbol" {...props}></Icon>
