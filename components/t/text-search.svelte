<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atfb8ubde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atfb8ubde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-search" {...props}></Icon>
