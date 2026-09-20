<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meyjvcahw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="meyjvcahw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:spacing-horizontal-16" {...props}></Icon>
