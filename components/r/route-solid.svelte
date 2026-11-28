<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysgkk-blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysgkk-blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:route-solid" {...props}></Icon>
