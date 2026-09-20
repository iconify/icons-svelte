<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8naembgy.css';
import '../../css/c/cnpgasf1a.css';
import '../../css/y/y7dn9kh7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="u8naembgy"><path class="cnpgasf1a"/><path class="y7dn9kh7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:warp" {...props}></Icon>
