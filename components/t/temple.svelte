<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq3m62bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dq3m62bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:temple" {...props}></Icon>
