<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dco4-8bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dco4-8bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round-check" {...props}></Icon>
