<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9u2iago.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eo9u2iago"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sparkles" {...props}></Icon>
