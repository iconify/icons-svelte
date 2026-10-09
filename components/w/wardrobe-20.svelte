<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj594fbcf.css';
import '../../css/a/avqgz5tna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jj594fbcf"/><path class="avqgz5tna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wardrobe-20" {...props}></Icon>
