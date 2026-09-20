<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95n9t5om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f95n9t5om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-small" {...props}></Icon>
