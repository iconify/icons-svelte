<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y28-sobij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y28-sobij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:streamlabs" {...props}></Icon>
