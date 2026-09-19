<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtzgfvdyl.css';
import '../../css/j/jqvrv4bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wtzgfvdyl"/><path class="jqvrv4bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-created-fill-12" {...props}></Icon>
