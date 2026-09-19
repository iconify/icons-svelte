<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfg0c2bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfg0c2bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:wifi" {...props}></Icon>
