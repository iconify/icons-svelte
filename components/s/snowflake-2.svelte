<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5vuvxbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="f5vuvxbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-2" {...props}></Icon>
