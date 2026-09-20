<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_ks2lbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_ks2lbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowflake-fill" {...props}></Icon>
