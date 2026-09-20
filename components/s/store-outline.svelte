<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubngjl5un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ubngjl5un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:store-outline" {...props}></Icon>
