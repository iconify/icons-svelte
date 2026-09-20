<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laaq2cmmd.css';
import '../../css/g/g948z0bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="laaq2cmmd"/><path clip-rule="evenodd" class="g948z0bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ui-panel-top-16" {...props}></Icon>
