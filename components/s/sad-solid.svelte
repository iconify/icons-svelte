<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c43vspbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c43vspbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:sad-solid" {...props}></Icon>
