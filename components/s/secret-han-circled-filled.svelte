<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5b94xbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t5b94xbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:secret-han-circled-filled" {...props}></Icon>
