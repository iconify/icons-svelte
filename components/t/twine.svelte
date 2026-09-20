<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a91r15bjt.css';
import '../../css/u/u50_rvyrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a91r15bjt"/><path class="u50_rvyrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:twine" {...props}></Icon>
