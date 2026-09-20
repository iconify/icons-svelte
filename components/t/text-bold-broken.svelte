<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh7m1x56q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh7m1x56q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-broken" {...props}></Icon>
