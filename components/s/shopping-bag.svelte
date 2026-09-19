<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/m/m9o65nmfm.css';
import '../../css/l/l-9noocio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="m9o65nmfm"/><path class="l-9noocio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shopping-bag" {...props}></Icon>
