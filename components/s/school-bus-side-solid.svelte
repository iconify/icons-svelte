<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w47oo1b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w47oo1b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:school-bus-side-solid" {...props}></Icon>
