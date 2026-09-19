<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do7mjdbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="do7mjdbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vials" {...props}></Icon>
