<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5wwf8b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":149,"height":30};
const content = `<path clip-rule="evenodd" class="r5wwf8b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tecno" {...props}></Icon>
