<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgw40dbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zgw40dbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:windows-alt3" {...props}></Icon>
