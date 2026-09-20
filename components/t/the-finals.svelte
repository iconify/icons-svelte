<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3x_a9b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x_a9b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-finals" {...props}></Icon>
