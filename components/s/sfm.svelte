<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4e9tjb-p.css';
import '../../css/r/r33vs8zyw.css';
import '../../css/w/w7guu_23n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4e9tjb-p"/><path clip-rule="evenodd" class="r33vs8zyw"/><path class="w7guu_23n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sfm" {...props}></Icon>
