<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zawcu5--r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zawcu5--r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:smallcircle-fill-circle" {...props}></Icon>
