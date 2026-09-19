<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjzveep3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gjzveep3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-fill-line-vertical-square" {...props}></Icon>
