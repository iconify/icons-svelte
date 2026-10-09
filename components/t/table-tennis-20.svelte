<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7tbn3bau.css';
import '../../css/u/uc95oo_ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7tbn3bau"/><path class="uc95oo_ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-tennis-20" {...props}></Icon>
