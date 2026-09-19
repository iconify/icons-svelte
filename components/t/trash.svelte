<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gur7w6b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gur7w6b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trash" {...props}></Icon>
