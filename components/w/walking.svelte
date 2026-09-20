<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wasx27b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wasx27b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:walking" {...props}></Icon>
