<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed3nujbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ed3nujbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:triangle-down" {...props}></Icon>
