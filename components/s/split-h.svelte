<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwu1xfb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kwu1xfb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:split-h" {...props}></Icon>
