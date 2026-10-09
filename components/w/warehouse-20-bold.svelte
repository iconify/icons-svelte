<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ll1nb8o.css';
import '../../css/z/zl7g3rzgo.css';
import '../../css/b/bi4oaoona.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e2ll1nb8o"/><path class="zl7g3rzgo"/><path class="bi4oaoona"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warehouse-20-bold" {...props}></Icon>
