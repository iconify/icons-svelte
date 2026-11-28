<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua7k72yme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ua7k72yme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:snowflake-duotone" {...props}></Icon>
