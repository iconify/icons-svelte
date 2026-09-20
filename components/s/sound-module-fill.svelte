<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pubj3xbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pubj3xbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sound-module-fill" {...props}></Icon>
