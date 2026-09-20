<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgrym0icu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgrym0icu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shower-head" {...props}></Icon>
