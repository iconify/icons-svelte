<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geode8baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="geode8baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sword" {...props}></Icon>
