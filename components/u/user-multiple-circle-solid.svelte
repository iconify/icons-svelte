<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6te2lb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g6te2lb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-multiple-circle-solid" {...props}></Icon>
