<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0vi13cyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0vi13cyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zap" {...props}></Icon>
