<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gydzj4ccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gydzj4ccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syrup-jug" {...props}></Icon>
