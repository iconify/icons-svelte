<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9wi1d8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9wi1d8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tumblr-square" {...props}></Icon>
