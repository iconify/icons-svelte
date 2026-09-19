<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-f7tacxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="d-f7tacxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tl" {...props}></Icon>
