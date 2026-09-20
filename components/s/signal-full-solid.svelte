<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hib610nnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hib610nnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:signal-full-solid" {...props}></Icon>
