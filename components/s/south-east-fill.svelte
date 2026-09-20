<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn1x1w7ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn1x1w7ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-fill" {...props}></Icon>
