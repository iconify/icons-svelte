<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk9vcn4yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk9vcn4yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-bolt" {...props}></Icon>
