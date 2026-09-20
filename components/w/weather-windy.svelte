<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk9hffbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk9hffbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-windy" {...props}></Icon>
