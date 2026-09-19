<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znag0hb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="znag0hb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:wodu" {...props}></Icon>
