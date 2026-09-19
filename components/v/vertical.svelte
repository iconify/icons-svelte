<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk01hcbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":691};
const content = `<path class="nk01hcbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:vertical" {...props}></Icon>
