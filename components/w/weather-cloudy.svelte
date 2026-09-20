<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee16c9d6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee16c9d6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:weather-cloudy" {...props}></Icon>
