<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml0h7rsel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ml0h7rsel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:snowflake" {...props}></Icon>
