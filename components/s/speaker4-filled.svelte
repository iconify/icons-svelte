<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvfmq8e6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvfmq8e6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speaker4-filled" {...props}></Icon>
