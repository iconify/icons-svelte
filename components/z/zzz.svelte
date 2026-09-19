<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq8hlouil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xq8hlouil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:zzz" {...props}></Icon>
