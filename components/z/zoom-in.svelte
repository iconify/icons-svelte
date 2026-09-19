<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_qh73eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs_qh73eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:zoom-in" {...props}></Icon>
