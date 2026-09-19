<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc3az4b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jc3az4b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-2" {...props}></Icon>
