<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td6ma8plu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="td6ma8plu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:unstage-all" {...props}></Icon>
