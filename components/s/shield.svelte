<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvhnz1kyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lvhnz1kyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield" {...props}></Icon>
