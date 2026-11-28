<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv8lb0fxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv8lb0fxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:snowflake-solid" {...props}></Icon>
