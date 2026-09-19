<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt7gntd-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kt7gntd-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:section" {...props}></Icon>
