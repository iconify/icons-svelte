<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncaoi_bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ncaoi_bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:teeth-open" {...props}></Icon>
