<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji8-djbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji8-djbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:viadeo" {...props}></Icon>
