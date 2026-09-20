<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a804f_bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a804f_bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sync-24" {...props}></Icon>
