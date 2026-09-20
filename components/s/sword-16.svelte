<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkarxnbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tkarxnbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sword-16" {...props}></Icon>
