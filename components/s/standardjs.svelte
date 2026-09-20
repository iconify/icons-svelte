<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnkv7ilvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnkv7ilvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:standardjs" {...props}></Icon>
