<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htqu3gbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="htqu3gbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tablet-landscape-fill" {...props}></Icon>
