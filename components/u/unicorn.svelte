<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9hauza-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y9hauza-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:unicorn" {...props}></Icon>
