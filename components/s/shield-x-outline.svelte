<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0_pgdyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wu0_pgdyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shield-x-outline" {...props}></Icon>
