<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml63hhbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ml63hhbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:separate-horizontal-16" {...props}></Icon>
