<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnq13b_qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gnq13b_qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:triangle-lefthalf-fill" {...props}></Icon>
