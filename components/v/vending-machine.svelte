<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9skjwb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9skjwb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-machine" {...props}></Icon>
