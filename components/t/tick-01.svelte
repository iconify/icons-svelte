<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl-5hpb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl-5hpb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-01" {...props}></Icon>
