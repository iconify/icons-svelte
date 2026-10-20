<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dld0-6buw.css';
import '../../css/b/bdj9pbbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dld0-6buw"/><path class="bdj9pbbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-color-20" {...props}></Icon>
