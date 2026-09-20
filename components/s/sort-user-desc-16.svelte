<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at8zgcbxx.css';
import '../../css/i/ixft57bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="at8zgcbxx"/><path clip-rule="evenodd" class="ixft57bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-user-desc-16" {...props}></Icon>
