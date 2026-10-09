<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht_47xbnf.css';
import '../../css/l/l6a3o_b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ht_47xbnf"/><path class="l6a3o_b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:temperature-20-bold" {...props}></Icon>
