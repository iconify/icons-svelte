<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tom9x8iww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tom9x8iww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:time-lapse-solid" {...props}></Icon>
