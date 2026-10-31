<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-hv9wb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-hv9wb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:snowflake-fill-round" {...props}></Icon>
