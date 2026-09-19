<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi_go-91g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mi_go-91g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-cli-fill-12" {...props}></Icon>
