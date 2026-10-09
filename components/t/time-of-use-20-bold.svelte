<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egmmgub_l.css';
import '../../css/u/u1hnyj58h.css';
import '../../css/b/b5hlbebng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="egmmgub_l"/><path class="u1hnyj58h"/><path class="b5hlbebng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:time-of-use-20-bold" {...props}></Icon>
