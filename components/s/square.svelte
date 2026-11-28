<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imu2dnx8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imu2dnx8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square" {...props}></Icon>
