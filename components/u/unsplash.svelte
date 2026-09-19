<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8xcojbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f8xcojbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:unsplash" {...props}></Icon>
