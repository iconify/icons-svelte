<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8skqjjki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k8skqjjki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sourceengine" {...props}></Icon>
