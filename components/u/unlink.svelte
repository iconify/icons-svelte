<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o46dvlbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o46dvlbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:unlink" {...props}></Icon>
