<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5shnlbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g5shnlbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-on-square" {...props}></Icon>
