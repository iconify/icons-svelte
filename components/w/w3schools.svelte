<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_-opib2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_-opib2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:w3schools" {...props}></Icon>
