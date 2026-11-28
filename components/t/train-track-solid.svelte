<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x73e8l8-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x73e8l8-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:train-track-solid" {...props}></Icon>
