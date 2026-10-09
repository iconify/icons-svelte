<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct17tacjl.css';
import '../../css/l/l9yqfvb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ct17tacjl"/><path class="l9yqfvb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tent-20" {...props}></Icon>
