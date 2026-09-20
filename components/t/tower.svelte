<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spt5sgiba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spt5sgiba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tower" {...props}></Icon>
