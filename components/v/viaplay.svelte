<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5jywb7ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5jywb7ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:viaplay" {...props}></Icon>
