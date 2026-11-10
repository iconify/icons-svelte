<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmn6akbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zmn6akbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-check-20-solid" {...props}></Icon>
