<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdhe4sbui.css';
import '../../css/x/xv7by3x_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdhe4sbui"/><path class="xv7by3x_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skip-next-bold" {...props}></Icon>
