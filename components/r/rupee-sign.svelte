<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne0nl4bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne0nl4bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rupee-sign" {...props}></Icon>
