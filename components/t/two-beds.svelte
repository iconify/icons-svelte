<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4kqi0kkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x4kqi0kkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:two-beds" {...props}></Icon>
