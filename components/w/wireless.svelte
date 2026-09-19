<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa0b9abac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fa0b9abac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wireless" {...props}></Icon>
