<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab6o8pbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6o8pbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xing" {...props}></Icon>
