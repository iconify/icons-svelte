<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt5xtacse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt5xtacse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-desc-24" {...props}></Icon>
