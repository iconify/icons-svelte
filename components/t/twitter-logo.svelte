<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm29eeclq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cm29eeclq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:twitter-logo" {...props}></Icon>
