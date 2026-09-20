<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_fg_bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="ia_fg_bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search-sm" {...props}></Icon>
