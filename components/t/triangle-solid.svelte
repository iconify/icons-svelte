<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys601bc8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys601bc8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-solid" {...props}></Icon>
