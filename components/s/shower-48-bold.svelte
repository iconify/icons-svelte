<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyxtagb8j.css';
import '../../css/p/pw9c74c9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dyxtagb8j"/><path class="pw9c74c9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shower-48-bold" {...props}></Icon>
