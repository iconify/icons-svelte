<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8g9ogb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8g9ogb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:spacing-medium-24" {...props}></Icon>
