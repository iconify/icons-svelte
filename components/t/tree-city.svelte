<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbqdb8bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gbqdb8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tree-city" {...props}></Icon>
