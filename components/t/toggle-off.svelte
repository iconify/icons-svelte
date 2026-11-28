<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzzzj3buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzzzj3buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:toggle-off" {...props}></Icon>
