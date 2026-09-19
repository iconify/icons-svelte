<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/o/o4nkozqud.css';
import '../../css/h/hdz8g6s7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="o4nkozqud"/><path class="hdz8g6s7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:ruble" {...props}></Icon>
