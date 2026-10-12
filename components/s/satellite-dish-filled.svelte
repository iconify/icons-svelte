<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zpdgb-u.css';
import '../../css/f/fuln-e3lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zpdgb-u"/><path class="fuln-e3lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:satellite-dish-filled" {...props}></Icon>
