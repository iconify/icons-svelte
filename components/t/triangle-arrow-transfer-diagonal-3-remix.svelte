<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2kyjzsvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r2kyjzsvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-transfer-diagonal-3-remix" {...props}></Icon>
