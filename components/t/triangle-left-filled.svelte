<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjk-fj_rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jjk-fj_rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-left-filled" {...props}></Icon>
