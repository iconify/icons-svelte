<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye0lxrj1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ye0lxrj1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:up-circle" {...props}></Icon>
