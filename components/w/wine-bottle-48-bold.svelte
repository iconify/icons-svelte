<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw-mwgb5w.css';
import '../../css/w/wt36fcmmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jw-mwgb5w"/><path class="wt36fcmmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-bottle-48-bold" {...props}></Icon>
