<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf80ehb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mf80ehb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:table-and-two-chairs-roof-and-walls" {...props}></Icon>
