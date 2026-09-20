<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl55uyk5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl55uyk5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:simpleicons" {...props}></Icon>
