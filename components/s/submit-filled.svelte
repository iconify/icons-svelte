<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmmj_iblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pmmj_iblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:submit-filled" {...props}></Icon>
