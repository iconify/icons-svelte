<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g39s4_i7q.css';
import '../../css/d/dbz_t_b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g39s4_i7q"/><path class="dbz_t_b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saf-20-bold" {...props}></Icon>
