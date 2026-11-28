<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo28wy1dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo28wy1dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shadow-solid" {...props}></Icon>
