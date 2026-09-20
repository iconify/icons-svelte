<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clfsm8btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clfsm8btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-typography" {...props}></Icon>
