<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dckm6kb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dckm6kb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-5" {...props}></Icon>
