<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ftgt0ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7ftgt0ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stars4" {...props}></Icon>
