<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejhjl4iog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejhjl4iog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sparks-solid" {...props}></Icon>
