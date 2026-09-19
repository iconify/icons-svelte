<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8zarbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8zarbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:snowflake-outline" {...props}></Icon>
