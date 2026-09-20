<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by3b00f7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="by3b00f7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:strikethrough" {...props}></Icon>
