<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak40dpbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ak40dpbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:snowflake-above-icicles" {...props}></Icon>
