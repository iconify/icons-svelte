<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh6d2wb4r.css';
import '../../css/a/aqx98_b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yh6d2wb4r"/><path class="aqx98_b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:storybook" {...props}></Icon>
