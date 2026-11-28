<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgedu3jvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgedu3jvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spline-solid" {...props}></Icon>
