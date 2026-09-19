<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbgflfbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nbgflfbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:three-button-mouse-alt" {...props}></Icon>
