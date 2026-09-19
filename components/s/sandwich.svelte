<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so0b9bbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="so0b9bbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sandwich" {...props}></Icon>
