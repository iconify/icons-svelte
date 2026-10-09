<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_xbna8j.css';
import '../../css/a/an6ptbjph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs_xbna8j"/><path class="an6ptbjph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-20" {...props}></Icon>
