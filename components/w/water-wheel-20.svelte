<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmwikhbug.css';
import '../../css/e/ekooj0b0b.css';
import '../../css/b/bvbkw3bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tmwikhbug"/><path class="ekooj0b0b"/><path class="bvbkw3bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-wheel-20" {...props}></Icon>
