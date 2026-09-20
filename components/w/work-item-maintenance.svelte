<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2rpab_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eb2rpab_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-maintenance" {...props}></Icon>
