<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9gm-41sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k9gm-41sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:table-and-two-chairs-pergola" {...props}></Icon>
