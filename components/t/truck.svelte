<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqe3c8lho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqe3c8lho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck" {...props}></Icon>
