<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esey5xbxp.css';
import '../../css/a/a7dbpzb-n.css';
import '../../css/b/b83b6belz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="esey5xbxp"/><path class="a7dbpzb-n"/><path class="b83b6belz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:solid" {...props}></Icon>
