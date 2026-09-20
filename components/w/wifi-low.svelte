<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajx912bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajx912bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-low" {...props}></Icon>
