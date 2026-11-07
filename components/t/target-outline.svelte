<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0cqj4bnv.css';
import '../../css/q/qmhcqtbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0cqj4bnv"/><path clip-rule="evenodd" class="qmhcqtbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:target-outline" {...props}></Icon>
