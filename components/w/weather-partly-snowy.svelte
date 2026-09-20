<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7f70rbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7f70rbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weather-partly-snowy" {...props}></Icon>
