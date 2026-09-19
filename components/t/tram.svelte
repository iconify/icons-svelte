<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqv2w248g.css';
import '../../css/v/vojqrkb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqv2w248g"/><path class="vojqrkb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tram" {...props}></Icon>
