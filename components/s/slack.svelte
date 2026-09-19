<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvbc83s6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zvbc83s6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:slack" {...props}></Icon>
