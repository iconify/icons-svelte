<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2w_dsb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2w_dsb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sparta" {...props}></Icon>
