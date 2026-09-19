<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m59-vibre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m59-vibre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni8349-circled" {...props}></Icon>
