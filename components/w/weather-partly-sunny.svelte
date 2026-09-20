<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lamduibsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lamduibsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:weather-partly-sunny" {...props}></Icon>
