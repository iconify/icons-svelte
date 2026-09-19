<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t48i01_4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t48i01_4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shift-fill" {...props}></Icon>
