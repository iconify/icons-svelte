<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmgd87b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmgd87b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:snowflake" {...props}></Icon>
