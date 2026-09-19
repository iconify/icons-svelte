<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpqlfhb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpqlfhb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xin" {...props}></Icon>
