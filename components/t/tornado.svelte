<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_0r-v9zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i_0r-v9zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tornado" {...props}></Icon>
