<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cunajyddk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cunajyddk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:survey-line" {...props}></Icon>
