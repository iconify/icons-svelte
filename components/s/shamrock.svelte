<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3bv18b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k3bv18b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:shamrock" {...props}></Icon>
