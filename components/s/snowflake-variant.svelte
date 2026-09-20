<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io83tst5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io83tst5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snowflake-variant" {...props}></Icon>
