<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvugenbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gvugenbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-grid-2x2-fill" {...props}></Icon>
