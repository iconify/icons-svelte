<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2trybrb.css';
import '../../css/y/yj8n5jbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ic2trybrb"/><path class="yj8n5jbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:umbrella-20" {...props}></Icon>
