<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edf2mabxb.css';
import '../../css/f/fijvpzgvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="fijvpzgvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-right-bold-duotone" {...props}></Icon>
