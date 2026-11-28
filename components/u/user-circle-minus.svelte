<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k19r2xnlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k19r2xnlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-circle-minus" {...props}></Icon>
