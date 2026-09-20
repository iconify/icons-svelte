<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fah1b-_sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fah1b-_sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-10-solid" {...props}></Icon>
