<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ontpq2bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ontpq2bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarem" {...props}></Icon>
