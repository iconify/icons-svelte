<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytseh3-cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ytseh3-cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:shared-database" {...props}></Icon>
