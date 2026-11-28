<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaa74ebsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaa74ebsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:summit" {...props}></Icon>
