<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_iszbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_iszbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-normal-light" {...props}></Icon>
