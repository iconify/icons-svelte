<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb5dbo-6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb5dbo-6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:seedling" {...props}></Icon>
