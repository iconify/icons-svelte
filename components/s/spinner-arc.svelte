<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nil9-lhla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nil9-lhla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:spinner-arc" {...props}></Icon>
