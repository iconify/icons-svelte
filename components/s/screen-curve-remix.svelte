<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uystlt1uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uystlt1uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:screen-curve-remix" {...props}></Icon>
