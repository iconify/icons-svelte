<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bawdkac8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bawdkac8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sort-desc-24" {...props}></Icon>
