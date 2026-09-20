<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp8_wcczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cp8_wcczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:vector" {...props}></Icon>
