<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oobshmhmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":111};
const content = `<path class="oobshmhmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:werf" {...props}></Icon>
