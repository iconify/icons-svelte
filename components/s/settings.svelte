<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3n-x2bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g3n-x2bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:settings" {...props}></Icon>
