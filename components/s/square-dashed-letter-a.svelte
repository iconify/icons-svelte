<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emjhn05hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="emjhn05hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-dashed-letter-a" {...props}></Icon>
