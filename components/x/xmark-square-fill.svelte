<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh_5xqbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xh_5xqbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark-square-fill" {...props}></Icon>
