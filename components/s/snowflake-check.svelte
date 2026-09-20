<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm-z46p2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm-z46p2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snowflake-check" {...props}></Icon>
