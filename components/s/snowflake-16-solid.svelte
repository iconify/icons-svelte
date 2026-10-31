<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv5n6wbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iv5n6wbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:snowflake-16-solid" {...props}></Icon>
