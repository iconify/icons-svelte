<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-w47cb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-w47cb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-info" {...props}></Icon>
