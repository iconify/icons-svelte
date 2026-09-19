<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne34-2bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ne34-2bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni54c8-box" {...props}></Icon>
