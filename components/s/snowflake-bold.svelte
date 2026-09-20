<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8t1-_2-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8t1-_2-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:snowflake-bold" {...props}></Icon>
