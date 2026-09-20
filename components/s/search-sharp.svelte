<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcc_mlbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcc_mlbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-sharp" {...props}></Icon>
