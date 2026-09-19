<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grc_u9byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grc_u9byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:snowflake" {...props}></Icon>
