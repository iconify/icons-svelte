<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx4pedbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fx4pedbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm-compact" {...props}></Icon>
