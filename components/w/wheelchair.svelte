<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jfuveou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p3jfuveou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wheelchair" {...props}></Icon>
