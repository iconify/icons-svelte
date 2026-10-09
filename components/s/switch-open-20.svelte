<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v44e49byk.css';
import '../../css/a/aw5adu44q.css';
import '../../css/c/ct5hu_u7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v44e49byk"/><path class="aw5adu44q"/><path class="ct5hu_u7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switch-open-20" {...props}></Icon>
