<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sws1rdbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sws1rdbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:shield-volcano" {...props}></Icon>
