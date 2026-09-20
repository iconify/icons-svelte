<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2c_x7bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2c_x7bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:snowflake-fill" {...props}></Icon>
