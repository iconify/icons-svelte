<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn6g75bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kn6g75bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:zodiac-10-flat" {...props}></Icon>
