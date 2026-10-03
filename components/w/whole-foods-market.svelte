<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiftlgbea.css';
import '../../css/i/ix4gy1bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":684.206};
const content = `<path class="kiftlgbea"/><path class="ix4gy1bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whole-foods-market" {...props}></Icon>
