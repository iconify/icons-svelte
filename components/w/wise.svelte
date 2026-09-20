<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_9wb0dpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_9wb0dpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wise" {...props}></Icon>
