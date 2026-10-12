<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p1wyuju3y.css';
import '../../css/v/vklcjt5rj.css';
import '../../css/t/t_62qsbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p1wyuju3y"/><path class="vklcjt5rj"/><path class="t_62qsbfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:store-duotone" {...props}></Icon>
