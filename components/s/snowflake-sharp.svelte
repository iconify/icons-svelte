<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj-a1cb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-a1cb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:snowflake-sharp" {...props}></Icon>
