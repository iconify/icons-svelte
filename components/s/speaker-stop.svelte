<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulzd8nbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulzd8nbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speaker-stop" {...props}></Icon>
