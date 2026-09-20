<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd8mp04wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd8mp04wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trivy" {...props}></Icon>
