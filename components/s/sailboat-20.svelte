<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1weu1kyu.css';
import '../../css/c/cjj4u9psh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h1weu1kyu"/><path class="cjj4u9psh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sailboat-20" {...props}></Icon>
