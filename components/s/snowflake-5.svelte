<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6f5--b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="s6f5--b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-5" {...props}></Icon>
