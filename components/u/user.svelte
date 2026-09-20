<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0_j2mtzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="q0_j2mtzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:user" {...props}></Icon>
