<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsbdr7opj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsbdr7opj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thermometer-snowflake" {...props}></Icon>
