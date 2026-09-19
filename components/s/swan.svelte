<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crqaz6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="crqaz6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:swan" {...props}></Icon>
