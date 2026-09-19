<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jts7qhbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jts7qhbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zikula" {...props}></Icon>
