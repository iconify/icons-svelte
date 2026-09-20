<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u25cw5bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u25cw5bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sun-snowflake-variant" {...props}></Icon>
