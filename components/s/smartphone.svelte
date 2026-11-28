<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k69vfgy3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k69vfgy3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smartphone" {...props}></Icon>
