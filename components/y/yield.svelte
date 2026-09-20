<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmt69hb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nmt69hb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:yield" {...props}></Icon>
