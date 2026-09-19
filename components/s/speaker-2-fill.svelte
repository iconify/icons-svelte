<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz5sbl4bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jz5sbl4bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-2-fill" {...props}></Icon>
