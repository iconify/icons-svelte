<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyo_zsbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="zyo_zsbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:searchfolder" {...props}></Icon>
