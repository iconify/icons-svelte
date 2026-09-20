<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7n6gybkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7n6gybkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:washer-alert" {...props}></Icon>
