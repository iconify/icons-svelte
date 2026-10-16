<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5vym_8fp.css';
import '../../css/z/z3ml8sb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k5vym_8fp"/><path class="z3ml8sb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-basket-48" {...props}></Icon>
