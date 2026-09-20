<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy519s08g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy519s08g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:snowflake" {...props}></Icon>
