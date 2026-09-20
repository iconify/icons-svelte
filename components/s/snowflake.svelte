<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ad4_l2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4ad4_l2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:snowflake" {...props}></Icon>
