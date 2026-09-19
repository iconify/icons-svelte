<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqvnn5rbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oqvnn5rbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1fae0" {...props}></Icon>
