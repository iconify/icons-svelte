<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at8zgcbxx.css';
import '../../css/b/bj_8uhrjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="at8zgcbxx"/><path clip-rule="evenodd" class="bj_8uhrjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-ranking-desc-16" {...props}></Icon>
