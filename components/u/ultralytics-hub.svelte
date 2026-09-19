<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrvyyj78y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yrvyyj78y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ultralytics-hub" {...props}></Icon>
