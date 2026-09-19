<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aix1bbbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="aix1bbbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-3" {...props}></Icon>
