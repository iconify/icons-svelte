<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8st6sboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v8st6sboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:z" {...props}></Icon>
