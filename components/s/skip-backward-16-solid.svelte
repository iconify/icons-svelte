<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbzn6k3gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hbzn6k3gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:skip-backward-16-solid" {...props}></Icon>
