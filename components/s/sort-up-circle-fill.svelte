<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-bnilbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i-bnilbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sort-up-circle-fill" {...props}></Icon>
