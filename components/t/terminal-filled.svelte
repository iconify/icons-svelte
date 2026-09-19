<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeo8jg0ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeo8jg0ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:terminal-filled" {...props}></Icon>
