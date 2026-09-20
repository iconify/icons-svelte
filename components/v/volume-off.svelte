<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpckdd_2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpckdd_2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:volume-off" {...props}></Icon>
