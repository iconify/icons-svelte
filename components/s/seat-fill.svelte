<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frc8xqbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frc8xqbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:seat-fill" {...props}></Icon>
