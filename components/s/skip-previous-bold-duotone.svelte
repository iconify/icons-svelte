<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dygia2sgr.css';
import '../../css/h/hbuiv42xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dygia2sgr"/><path class="hbuiv42xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skip-previous-bold-duotone" {...props}></Icon>
