<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqykbbfle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqykbbfle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:usergroup-add" {...props}></Icon>
