<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8yeuabmx.css';
import '../../css/o/olvwwtpsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u8yeuabmx"/><path class="olvwwtpsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:share-external-16" {...props}></Icon>
