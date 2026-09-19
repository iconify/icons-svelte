<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjnt3k6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="scjnt3k6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:snowflake" {...props}></Icon>
