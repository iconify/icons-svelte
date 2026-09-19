<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__oynb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q__oynb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:table-cells-row-unlock" {...props}></Icon>
