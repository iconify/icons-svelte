<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a29x5nygp.css';
import '../../css/y/yq9xkk4gp.css';
import '../../css/s/sd5zehitt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a29x5nygp"/><path class="yq9xkk4gp"/><path class="sd5zehitt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-sock-20-bold" {...props}></Icon>
