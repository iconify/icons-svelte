<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fib_oobro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fib_oobro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:salesforce" {...props}></Icon>
