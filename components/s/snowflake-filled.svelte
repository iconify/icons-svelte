<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1127jm3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1127jm3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:snowflake-filled" {...props}></Icon>
