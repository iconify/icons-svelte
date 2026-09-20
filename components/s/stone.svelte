<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzb8q72ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pzb8q72ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stone" {...props}></Icon>
