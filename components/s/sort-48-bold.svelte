<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oljuiobcr.css';
import '../../css/e/eecmlgb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oljuiobcr"/><path class="eecmlgb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-48-bold" {...props}></Icon>
