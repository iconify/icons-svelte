<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji3oo10aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji3oo10aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tablet-filled" {...props}></Icon>
