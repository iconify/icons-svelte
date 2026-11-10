<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjsjm40yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zjsjm40yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:wifi-slash-16-solid" {...props}></Icon>
