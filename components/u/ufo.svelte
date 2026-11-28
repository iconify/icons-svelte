<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb7v1ub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb7v1ub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ufo" {...props}></Icon>
