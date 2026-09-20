<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3qy1r37f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i3qy1r37f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sign-in-alt" {...props}></Icon>
